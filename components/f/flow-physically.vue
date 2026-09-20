<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5ifw4byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="d5ifw4byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:flow-physically" /></template>
