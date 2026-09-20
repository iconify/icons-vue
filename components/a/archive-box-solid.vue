<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrz8h778r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zrz8h778r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:archive-box-solid" /></template>
