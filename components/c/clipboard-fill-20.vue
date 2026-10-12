<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnbt48bet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xnbt48bet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clipboard-fill-20" /></template>
