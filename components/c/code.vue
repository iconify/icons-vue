<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul_akom3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ul_akom3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:code" /></template>
