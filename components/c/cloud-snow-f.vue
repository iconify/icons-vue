<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-4shmbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="q-4shmbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:cloud-snow-f" /></template>
