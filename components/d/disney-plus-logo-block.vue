<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8u5iic6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m8u5iic6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:disney-plus-logo-block" /></template>
