<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei5dzwmfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ei5dzwmfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:duck" /></template>
