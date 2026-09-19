<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlp09obxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rlp09obxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:iost" /></template>
