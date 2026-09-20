<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc011j55m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nc011j55m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:banknote-stack" /></template>
