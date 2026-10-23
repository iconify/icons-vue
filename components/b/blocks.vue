<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nry19sbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nry19sbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:blocks" /></template>
