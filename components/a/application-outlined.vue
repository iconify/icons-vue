<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3jmkedbk.css';
import '../../css/e/epdjs8byf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVG3Qrzedlb" class="w3jmkedbk"/></defs><path class="epdjs8byf"/><use href="#SVG3Qrzedlb"/><use href="#SVG3Qrzedlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:application-outlined" /></template>
