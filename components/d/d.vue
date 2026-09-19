<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-snw_bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="v-snw_bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:d" /></template>
