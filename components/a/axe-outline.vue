<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9w2xqbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="o9w2xqbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:axe-outline" /></template>
