<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-o9xacme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t-o9xacme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:folder-block-solid" /></template>
