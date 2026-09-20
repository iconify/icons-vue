<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usc8o6-bs.css';
import '../../css/r/rqhj3y1_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usc8o6-bs"/><path class="rqhj3y1_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:burger-drink" /></template>
