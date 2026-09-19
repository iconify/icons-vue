<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky4n3ccwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ky4n3ccwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hourglass-50-bold" /></template>
