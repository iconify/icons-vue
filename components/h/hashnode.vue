<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw4634b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw4634b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:hashnode" /></template>
