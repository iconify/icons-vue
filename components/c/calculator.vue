<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0dd72brq.css';
import '../../css/v/v1z4zvbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0dd72brq"/><path class="v1z4zvbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:calculator" /></template>
