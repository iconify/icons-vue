<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnvjrjbfl.css';
import '../../css/o/o7x01qbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nnvjrjbfl"/><path class="o7x01qbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:at" /></template>
