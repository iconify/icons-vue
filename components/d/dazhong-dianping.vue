<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad8f__bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad8f__bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dazhong-dianping" /></template>
