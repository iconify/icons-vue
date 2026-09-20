<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oku8xrlhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oku8xrlhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-bridge-logo-solid" /></template>
