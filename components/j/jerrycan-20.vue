<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_reqgbqv.css';
import '../../css/l/la3dn2r7d.css';
import '../../css/u/ubtst-b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n_reqgbqv"/><path class="la3dn2r7d"/><path class="ubtst-b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:jerrycan-20" /></template>
