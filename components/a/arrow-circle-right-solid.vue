<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egh4-2-bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egh4-2-bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:arrow-circle-right-solid" /></template>
