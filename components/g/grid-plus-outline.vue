<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg_xm2btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg_xm2btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:grid-plus-outline" /></template>
