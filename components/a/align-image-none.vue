<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqw--zbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqw--zbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:align-image-none" /></template>
