<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvk7dfb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="cvk7dfb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:leak-remove" /></template>
