<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej5pdo-_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ej5pdo-_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:authgear-light" /></template>
