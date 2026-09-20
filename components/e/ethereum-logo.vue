<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycarj_sir.css';
import '../../css/d/d2npymh2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycarj_sir"/><path class="d2npymh2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ethereum-logo" /></template>
