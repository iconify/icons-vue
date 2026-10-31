<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbwo-2beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbwo-2beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-plus-round" /></template>
