<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn3-n0bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pn3-n0bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:list-alt-solid" /></template>
