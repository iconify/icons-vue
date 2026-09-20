<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ody0k2bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ody0k2bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:forward-step" /></template>
