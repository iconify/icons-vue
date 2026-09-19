<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgs7_xe4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgs7_xe4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:arrow-left" /></template>
