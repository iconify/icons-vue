<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adm28hbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adm28hbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:crop-7-5" /></template>
