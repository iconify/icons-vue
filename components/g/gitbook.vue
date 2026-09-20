<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4drh5_en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4drh5_en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gitbook" /></template>
