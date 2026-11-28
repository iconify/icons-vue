<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nngue2ksh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nngue2ksh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:gavel" /></template>
