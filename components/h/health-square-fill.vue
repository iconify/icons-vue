<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txyd36pzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txyd36pzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:health-square-fill" /></template>
