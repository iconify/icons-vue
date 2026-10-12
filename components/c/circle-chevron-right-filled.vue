<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o41_nhbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o41_nhbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-chevron-right-filled" /></template>
