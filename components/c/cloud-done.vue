<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v21ek9egt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="v21ek9egt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:cloud-done" /></template>
