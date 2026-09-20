<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpri_ybdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpri_ybdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:battery-charge-fill" /></template>
