<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfwdc41th.css';
import '../../css/l/lci61mkfz.css';
import '../../css/a/a8kb4gb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yfwdc41th"/><path class="lci61mkfz"/><path class="a8kb4gb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-search-stroke-20" /></template>
