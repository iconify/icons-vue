<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hspiz0b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hspiz0b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:emergency-stop" /></template>
