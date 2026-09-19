<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy6o8dbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy6o8dbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:delivery-bold" /></template>
