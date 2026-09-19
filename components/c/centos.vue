<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn599lbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="pn599lbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:centos" /></template>
