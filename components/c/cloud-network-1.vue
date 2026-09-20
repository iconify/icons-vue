<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8c084gqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d8c084gqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:cloud-network-1" /></template>
