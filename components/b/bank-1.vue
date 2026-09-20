<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxxo2obwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxxo2obwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:bank-1" /></template>
