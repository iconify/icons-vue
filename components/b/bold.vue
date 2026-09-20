<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmlg3s19r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="pmlg3s19r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bold" /></template>
