<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw689ii1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="sw689ii1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:italic" /></template>
