<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo3ab_-fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo3ab_-fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:audacity" /></template>
