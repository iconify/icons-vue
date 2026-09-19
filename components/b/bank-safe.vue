<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5i_e_qgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f5i_e_qgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:bank-safe" /></template>
