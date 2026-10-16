<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f36_sk0cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f36_sk0cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:focus-48" /></template>
