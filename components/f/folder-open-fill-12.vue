<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mblcg4bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mblcg4bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:folder-open-fill-12" /></template>
