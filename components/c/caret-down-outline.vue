<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvx0x29yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gvx0x29yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:caret-down-outline" /></template>
