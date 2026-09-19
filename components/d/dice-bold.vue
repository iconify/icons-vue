<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-9eorpun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="y-9eorpun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:dice-bold" /></template>
