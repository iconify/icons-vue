<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alw736d5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="alw736d5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:check-circle-bold" /></template>
