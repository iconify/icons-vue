<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt_d2pbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt_d2pbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:backtop" /></template>
