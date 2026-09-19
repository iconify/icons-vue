<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp_ji1bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":512};
const content = `<path class="zp_ji1bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:lego" /></template>
