<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxo_lqb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxo_lqb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:clipboard-x-solid" /></template>
