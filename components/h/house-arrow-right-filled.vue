<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbsonz3ob.css';
import '../../css/m/mtfo425qq.css';
import '../../css/v/vu0p8sbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbsonz3ob"/><path class="mtfo425qq"/><path class="vu0p8sbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:house-arrow-right-filled" /></template>
