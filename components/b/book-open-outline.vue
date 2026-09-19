<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzu6-ccig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="bzu6-ccig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:book-open-outline" /></template>
