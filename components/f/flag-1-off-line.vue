<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj4z4bhxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj4z4bhxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flag-1-off-line" /></template>
