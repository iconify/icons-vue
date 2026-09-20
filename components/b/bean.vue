<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw99ufbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw99ufbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bean" /></template>
