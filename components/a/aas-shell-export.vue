<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxo764bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxo764bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:aas-shell-export" /></template>
