<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiu53hmpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aiu53hmpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:join-inner" /></template>
