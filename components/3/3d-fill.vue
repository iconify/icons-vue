<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpv4762am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kpv4762am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:3d-fill" /></template>
