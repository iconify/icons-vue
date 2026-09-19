<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx9-vt3cm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="lx9-vt3cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:dog" /></template>
