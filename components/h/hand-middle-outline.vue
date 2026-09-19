<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi6j4pa6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="pi6j4pa6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-middle-outline" /></template>
