<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_sdbxlje.css';
import '../../css/r/rs1l3rb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_sdbxlje"/><path class="rs1l3rb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bscpad" /></template>
