<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_nz00ruv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_nz00ruv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:app-store" /></template>
