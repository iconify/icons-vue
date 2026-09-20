<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qknldwu4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qknldwu4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:group" /></template>
