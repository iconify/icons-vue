<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh4cx0b9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="sh4cx0b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:cloud-disconnect" /></template>
