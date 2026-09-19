<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw6qw7b0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="bw6qw7b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hammer-outline" /></template>
