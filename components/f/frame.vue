<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blvm6x9ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blvm6x9ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:frame" /></template>
