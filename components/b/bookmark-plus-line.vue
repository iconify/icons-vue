<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgtspcczu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgtspcczu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:bookmark-plus-line" /></template>
