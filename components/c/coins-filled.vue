<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxbs97bbo.css';
import '../../css/v/v_sj4-bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxbs97bbo"/><circle class="v_sj4-bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:coins-filled" /></template>
