<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkocd3rkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="zkocd3rkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:eight-bold" /></template>
