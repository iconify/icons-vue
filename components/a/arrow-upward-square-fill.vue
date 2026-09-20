<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnoo_kb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cnoo_kb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-upward-square-fill" /></template>
