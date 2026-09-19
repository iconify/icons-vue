<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl0gd1q_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl0gd1q_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-share" /></template>
