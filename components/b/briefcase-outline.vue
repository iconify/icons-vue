<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmwg3mbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="bmwg3mbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:briefcase-outline" /></template>
