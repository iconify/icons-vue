<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxevnnfbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxevnnfbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bookmark-off-solid" /></template>
