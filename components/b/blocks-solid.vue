<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbym7lbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbym7lbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:blocks-solid" /></template>
