<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjgp20b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pjgp20b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-gabled-building-with-chimney" /></template>
