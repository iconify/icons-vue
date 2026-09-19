<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-r8ydbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="m-r8ydbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:envelope-open-outline" /></template>
