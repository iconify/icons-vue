<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1nrsbcrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="a1nrsbcrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:bars-3-bottom-center-20-solid" /></template>
