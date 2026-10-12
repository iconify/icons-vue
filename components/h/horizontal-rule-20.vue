<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn4p0rgtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pn4p0rgtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:horizontal-rule-20" /></template>
