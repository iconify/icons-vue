<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm5z_rb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="vm5z_rb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:ankh" /></template>
