<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r904zvwij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="r904zvwij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:headset" /></template>
