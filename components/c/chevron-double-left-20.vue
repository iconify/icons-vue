<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypvhh7b9x.css';
import '../../css/w/w2aqxxbkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ypvhh7b9x"/><path class="w2aqxxbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-double-left-20" /></template>
