<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t96x9qtfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t96x9qtfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ferretdb-light" /></template>
