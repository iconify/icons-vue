<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnf9n1bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nnf9n1bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:camera-square-bold" /></template>
