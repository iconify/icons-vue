<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh_t_956l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="dh_t_956l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:border-none" /></template>
