<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8caiw2rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q8caiw2rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:four" /></template>
