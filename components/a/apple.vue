<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z708ukb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="z708ukb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:apple" /></template>
