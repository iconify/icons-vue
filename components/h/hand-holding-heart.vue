<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sca024b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="sca024b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-holding-heart" /></template>
