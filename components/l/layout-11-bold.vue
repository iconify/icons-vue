<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbem5n73m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lbem5n73m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:layout-11-bold" /></template>
