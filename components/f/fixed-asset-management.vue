<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwynisbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rwynisbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:fixed-asset-management" /></template>
