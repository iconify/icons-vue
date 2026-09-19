<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv2z275ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nv2z275ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-smile-beam" /></template>
