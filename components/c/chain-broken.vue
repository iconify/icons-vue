<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di2cjrb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="di2cjrb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:chain-broken" /></template>
