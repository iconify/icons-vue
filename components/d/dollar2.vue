<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duprv2fpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="duprv2fpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:dollar2" /></template>
