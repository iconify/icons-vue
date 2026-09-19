<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrsrqfkrg.css';
import '../../css/l/lw_rdhb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrsrqfkrg"/><path class="lw_rdhb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alarm-alt-filled" /></template>
