<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3u1aubzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3u1aubzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:capsule-line" /></template>
