<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdb9d7b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pdb9d7b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:forrst-logo-solid" /></template>
