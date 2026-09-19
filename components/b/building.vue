<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjq3ac0dg.css';
import '../../css/i/ipjtrphds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjq3ac0dg"/><path class="ipjtrphds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:building" /></template>
