<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up5bodb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="up5bodb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:cutter" /></template>
