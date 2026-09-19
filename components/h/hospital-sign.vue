<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn80c9n7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="nn80c9n7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hospital-sign" /></template>
