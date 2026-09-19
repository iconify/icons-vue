<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phfy6f6ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="phfy6f6ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:gift-2-outline" /></template>
