<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4p_kzgss.css';
import '../../css/y/yz_54e91d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4p_kzgss"/><path class="yz_54e91d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-square-outline" /></template>
