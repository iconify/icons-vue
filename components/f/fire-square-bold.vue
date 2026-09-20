<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amyujzb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="amyujzb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fire-square-bold" /></template>
