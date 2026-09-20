<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_d8u_bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_d8u_bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:direction-right-fill" /></template>
