<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtsg4ndep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jtsg4ndep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ascending-alphabetical-order-solid" /></template>
