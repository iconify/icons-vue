<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w99tz1j_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w99tz1j_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:expand-down-stop" /></template>
