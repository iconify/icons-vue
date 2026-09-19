<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akrx86noy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="akrx86noy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery-25" /></template>
