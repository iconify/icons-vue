<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq9q0tbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kq9q0tbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:at-sign" /></template>
