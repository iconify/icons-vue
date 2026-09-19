<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6j1gybkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k6j1gybkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bubble-message-talk" /></template>
