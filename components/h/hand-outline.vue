<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm7o27bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zm7o27bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-outline" /></template>
