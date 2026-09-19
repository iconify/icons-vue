<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx9m-lbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bx9m-lbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:bluetooth-fill" /></template>
