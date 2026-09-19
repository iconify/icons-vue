<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miifqw2bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1664};
const content = `<path class="miifqw2bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:chair-alt" /></template>
