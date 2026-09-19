<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nic15ybst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nic15ybst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lightning-bolt-fill-12" /></template>
