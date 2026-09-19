<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftemw-a2c.css';
import '../../css/z/zfls42b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftemw-a2c"/><path class="zfls42b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cupboard-alt" /></template>
