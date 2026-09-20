<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drgj1zbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="drgj1zbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:bulb2" /></template>
