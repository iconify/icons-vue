<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eej-vvbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eej-vvbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hilo" /></template>
