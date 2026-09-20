<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2t9lobhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2t9lobhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:forbid-circle-fill" /></template>
