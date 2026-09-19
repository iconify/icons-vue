<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-__3ot9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="g-__3ot9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grid-lg-outline" /></template>
