<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8ipqhb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":960};
const content = `<path class="c8ipqhb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:insertpicturecenter" /></template>
