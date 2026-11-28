<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxggxp1wz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxggxp1wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:home-alert" /></template>
