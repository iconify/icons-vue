<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts2tgjjid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ts2tgjjid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:eye-lashes-outline" /></template>
