<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9v_qkbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9v_qkbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:la" /></template>
