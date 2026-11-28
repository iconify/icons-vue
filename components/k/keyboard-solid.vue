<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgi_gv_ea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgi_gv_ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:keyboard-solid" /></template>
