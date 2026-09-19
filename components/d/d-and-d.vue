<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_ksh4r_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="o_ksh4r_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:d-and-d" /></template>
