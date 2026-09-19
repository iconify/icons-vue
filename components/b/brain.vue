<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkabjpgaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="bkabjpgaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:brain" /></template>
