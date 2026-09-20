<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb7-bug3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb7-bug3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bentley" /></template>
