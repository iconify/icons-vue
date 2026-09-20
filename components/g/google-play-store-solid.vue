<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c965ddcsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c965ddcsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:google-play-store-solid" /></template>
