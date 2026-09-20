<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtxzj-b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dtxzj-b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:bookmark" /></template>
