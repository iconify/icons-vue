<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z69_crzqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z69_crzqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:house-plus-gloss" /></template>
