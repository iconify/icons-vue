<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwz_shb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="iwz_shb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:align-items-center" /></template>
