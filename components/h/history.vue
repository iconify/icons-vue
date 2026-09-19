<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc3gbjbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fc3gbjbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:history" /></template>
