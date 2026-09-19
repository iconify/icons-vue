<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m515emb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":472};
const content = `<path class="m515emb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:bus-london" /></template>
