<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyk3zk00o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wyk3zk00o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ape" /></template>
