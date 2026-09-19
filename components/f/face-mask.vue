<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5ej4pbho.css';
import '../../css/p/p_f9wqv2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5ej4pbho"/><path class="p_f9wqv2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:face-mask" /></template>
