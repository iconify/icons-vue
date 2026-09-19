<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e58o2jowk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="e58o2jowk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:lightning-1-outline" /></template>
