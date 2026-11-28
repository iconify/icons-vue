<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifj42nz6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifj42nz6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ampersand" /></template>
