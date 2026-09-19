<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sslr2nb7i.css';
import '../../css/y/y36i_nbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sslr2nb7i"/><path class="y36i_nbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-sidebar" /></template>
