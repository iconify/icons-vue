<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkdjwc4-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="lkdjwc4-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:align-slash-duo" /></template>
