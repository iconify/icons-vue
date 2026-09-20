<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s31oqeb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s31oqeb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:house-with-flag" /></template>
