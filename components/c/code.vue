<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl8o-nbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="pl8o-nbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:code" /></template>
