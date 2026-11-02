<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0_iltb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0_iltb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:axis-3d-line" /></template>
