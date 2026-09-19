<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-cmjqifn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="h-cmjqifn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:eye-1-slash-outline" /></template>
