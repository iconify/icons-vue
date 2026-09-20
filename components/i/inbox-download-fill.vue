<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me9fu616u.css';
import '../../css/b/blt65bfce.css';
import '../../css/u/utyj_2zie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me9fu616u"/><path class="blt65bfce"/><path class="utyj_2zie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:inbox-download-fill" /></template>
