<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eio5m-zyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eio5m-zyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:globe-tag" /></template>
