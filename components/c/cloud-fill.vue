<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1rn9v5yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w1rn9v5yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:cloud-fill" /></template>
