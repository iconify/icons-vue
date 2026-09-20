<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv0rs1cdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gv0rs1cdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:3ds-max-logo-solid" /></template>
