<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmfenk13t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmfenk13t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-fill-round" /></template>
