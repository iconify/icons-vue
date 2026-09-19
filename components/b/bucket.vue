<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmshjo7qm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="vmshjo7qm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bucket" /></template>
