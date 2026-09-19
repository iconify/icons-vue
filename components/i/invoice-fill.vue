<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3xbg8byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k3xbg8byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:invoice-fill" /></template>
