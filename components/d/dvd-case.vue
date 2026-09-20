<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx7je-blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tx7je-blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dvd-case" /></template>
