<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri--i_b-k.css';
import '../../css/v/vg2qp3oat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ri--i_b-k"/><path class="vg2qp3oat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:cloud-sun-fill-20" /></template>
