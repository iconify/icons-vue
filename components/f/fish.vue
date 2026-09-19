<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9h4j1-rk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":472};
const content = `<path class="a9h4j1-rk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:fish" /></template>
