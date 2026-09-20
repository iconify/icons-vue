<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy2yqxtsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zy2yqxtsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:link-chain-flat" /></template>
