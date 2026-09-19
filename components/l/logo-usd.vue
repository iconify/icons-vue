<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrabqj9ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yrabqj9ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-usd" /></template>
