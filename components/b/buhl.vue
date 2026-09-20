<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lff5ccbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lff5ccbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:buhl" /></template>
