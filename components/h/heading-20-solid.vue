<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0s7lfbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w0s7lfbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:heading-20-solid" /></template>
