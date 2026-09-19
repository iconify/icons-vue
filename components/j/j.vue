<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyy96ws_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vyy96ws_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:j" /></template>
