<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxjgpfbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sxjgpfbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:flip-horizontal-filled" /></template>
