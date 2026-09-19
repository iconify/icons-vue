<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3x7q5b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p3x7q5b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:hide-sidebar" /></template>
