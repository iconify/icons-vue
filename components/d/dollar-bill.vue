<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7zdzsp8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="v7zdzsp8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:dollar-bill" /></template>
