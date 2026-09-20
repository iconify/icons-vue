<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooyaa4bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ooyaa4bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:anchor" /></template>
