<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpxmdzbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dpxmdzbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:circle-with-fallout-shelter-symbol" /></template>
