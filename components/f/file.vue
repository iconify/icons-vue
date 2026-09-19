<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erj8o9bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="erj8o9bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:file" /></template>
