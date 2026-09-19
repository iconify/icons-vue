<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pppgz_8mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pppgz_8mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:circle-chevron-left" /></template>
