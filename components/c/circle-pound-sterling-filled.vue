<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1879yhkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i1879yhkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-pound-sterling-filled" /></template>
