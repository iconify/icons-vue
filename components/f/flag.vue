<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbpey7bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cbpey7bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:flag" /></template>
