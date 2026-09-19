<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs4ejwyhj.css';
import '../../css/f/fa6uf3bbr.css';
import '../../css/h/haqwlo80j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="xs4ejwyhj"/><path class="fa6uf3bbr"/><path class="haqwlo80j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:jquery" /></template>
