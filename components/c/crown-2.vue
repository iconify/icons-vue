<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_1wvtowb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_1wvtowb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:crown-2" /></template>
