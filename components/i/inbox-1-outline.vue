<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukfdctbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ukfdctbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:inbox-1-outline" /></template>
