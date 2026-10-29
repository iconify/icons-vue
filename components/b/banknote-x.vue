<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-2s-5brl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-2s-5brl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:banknote-x" /></template>
