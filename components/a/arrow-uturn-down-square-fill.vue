<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8odnb1pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="w8odnb1pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-uturn-down-square-fill" /></template>
