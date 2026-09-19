<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcf7diewg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wcf7diewg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:glyphs" /></template>
