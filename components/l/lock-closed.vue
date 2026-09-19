<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2k62cc3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a2k62cc3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:lock-closed" /></template>
