<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgu1w2bgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":528};
const content = `<path class="fgu1w2bgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:home" /></template>
