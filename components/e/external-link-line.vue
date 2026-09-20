<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcmlbv4_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcmlbv4_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:external-link-line" /></template>
