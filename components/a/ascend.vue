<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv_ovvbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv_ovvbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:ascend" /></template>
