<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_wmkzbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="z_wmkzbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-horns-bold" /></template>
