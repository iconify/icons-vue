<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1_6vmh0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1_6vmh0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:evmos" /></template>
