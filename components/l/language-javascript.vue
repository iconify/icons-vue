<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pum6gtbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="pum6gtbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:language-javascript" /></template>
