<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itxscdiqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="itxscdiqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:dice-bold" /></template>
