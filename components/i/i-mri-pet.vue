<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjevd7biy.css';
import '../../css/g/gkse_6x1h.css';
import '../../css/v/v-w-_tb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hjevd7biy"/><path class="gkse_6x1h"/><path class="v-w-_tb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-mri-pet" /></template>
