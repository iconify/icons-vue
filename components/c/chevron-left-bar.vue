<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onur9sryp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="onur9sryp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chevron-left-bar" /></template>
