<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvzkb_bhc.css';
import '../../css/r/rhvegq0-t.css';
import '../../css/i/i0x2txbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hvzkb_bhc"/><path class="rhvegq0-t"/><path class="i0x2txbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-search-20-bold" /></template>
