<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb1rppbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lb1rppbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:gold-solid" /></template>
