<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw-94rbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="kw-94rbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:greekcolumn" /></template>
