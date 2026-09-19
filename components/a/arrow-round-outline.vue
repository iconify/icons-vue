<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6_uqk3gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="t6_uqk3gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-round-outline" /></template>
