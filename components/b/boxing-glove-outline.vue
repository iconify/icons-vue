<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wye1xtbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="wye1xtbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:boxing-glove-outline" /></template>
