<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibja0x6pk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibja0x6pk primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bold-duotone" /></template>
