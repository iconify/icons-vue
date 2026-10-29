<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twy10abre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twy10abre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-ordered-solid" /></template>
