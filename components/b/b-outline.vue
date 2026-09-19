<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq1no1b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="bq1no1b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:b-outline" /></template>
