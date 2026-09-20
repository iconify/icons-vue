<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjqc-qb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mjqc-qb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hat-2-fill" /></template>
