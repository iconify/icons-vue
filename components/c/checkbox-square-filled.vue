<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_kpj8bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_kpj8bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:checkbox-square-filled" /></template>
