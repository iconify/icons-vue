<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrhwmpbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wrhwmpbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:loaf-of-pan-bread-with-steam" /></template>
