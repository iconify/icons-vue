<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdujazbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdujazbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:cloud" /></template>
