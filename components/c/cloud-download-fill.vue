<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5_zu7bdk.css';
import '../../css/e/elcyybcku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGdPdPCXCl" class="f5_zu7bdk"/><path id="SVGXdxzPddm" class="elcyybcku"/></defs><use href="#SVGdPdPCXCl"/><use href="#SVGXdxzPddm"/><use href="#SVGdPdPCXCl"/><use href="#SVGXdxzPddm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:cloud-download-fill" /></template>
