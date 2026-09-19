<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv3kr87mm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="bv3kr87mm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:barcode" /></template>
