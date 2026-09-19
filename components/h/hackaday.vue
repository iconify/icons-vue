<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oue1_lxyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oue1_lxyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:hackaday" /></template>
