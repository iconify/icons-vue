<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv0q8b-8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vv0q8b-8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:hourglass" /></template>
