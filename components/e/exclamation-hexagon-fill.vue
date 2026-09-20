<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h80ps7bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h80ps7bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:exclamation-hexagon-fill" /></template>
