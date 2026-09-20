<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hckli2bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hckli2bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:controller-wireless-solid" /></template>
