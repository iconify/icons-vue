<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es7-cbc_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="es7-cbc_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:aqt" /></template>
