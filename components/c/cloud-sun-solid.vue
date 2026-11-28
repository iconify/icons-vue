<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdb1cx7ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdb1cx7ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-sun-solid" /></template>
