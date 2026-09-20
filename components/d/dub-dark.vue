<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syeeeyb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path clip-rule="evenodd" class="syeeeyb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dub-dark" /></template>
