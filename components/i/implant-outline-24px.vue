<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inyiadczw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inyiadczw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:implant-outline-24px" /></template>
