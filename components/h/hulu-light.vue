<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trlfrfbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":243.5,"height":80};
const content = `<path clip-rule="evenodd" class="trlfrfbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hulu-light" /></template>
