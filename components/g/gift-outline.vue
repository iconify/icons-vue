<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7kqt_bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="n7kqt_bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:gift-outline" /></template>
