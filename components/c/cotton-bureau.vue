<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-i_uiwdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s-i_uiwdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:cotton-bureau" /></template>
