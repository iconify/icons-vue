<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myksc3vum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myksc3vum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mail-pen" /></template>
