<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm39c7bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":24};
const content = `<path class="xm39c7bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:bitcoin" /></template>
