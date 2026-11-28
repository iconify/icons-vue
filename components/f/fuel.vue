<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnwo09bcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnwo09bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:fuel" /></template>
