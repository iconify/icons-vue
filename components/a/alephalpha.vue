<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-0f5sb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-0f5sb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:alephalpha" /></template>
