<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie6mjcplv.css';
import '../../css/v/v_suxqb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie6mjcplv"/><path class="v_suxqb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:coffee-bean" /></template>
