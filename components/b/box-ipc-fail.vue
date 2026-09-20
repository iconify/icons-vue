<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4zn-mv5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="t4zn-mv5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:box-ipc-fail" /></template>
