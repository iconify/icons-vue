<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv2hpe3im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wv2hpe3im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arkansas-with-capital-star" /></template>
