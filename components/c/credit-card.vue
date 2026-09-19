<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwcutcvzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rwcutcvzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:credit-card" /></template>
