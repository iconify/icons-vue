<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4n-xeb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="l4n-xeb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:f-outline" /></template>
