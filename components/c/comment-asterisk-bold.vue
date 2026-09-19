<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egwn_np2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="egwn_np2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-asterisk-bold" /></template>
