<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv_n7dmdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kv_n7dmdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:linkedin-fill-12" /></template>
