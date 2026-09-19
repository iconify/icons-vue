<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7i1dpmbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="c7i1dpmbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-holding-bold" /></template>
