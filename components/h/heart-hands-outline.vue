<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok6lomhrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ok6lomhrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heart-hands-outline" /></template>
