<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfbuhbbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfbuhbbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:cloud-alt-01-filled" /></template>
