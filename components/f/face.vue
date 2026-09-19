<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qilianfni.css';
import '../../css/i/in2__ug-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qilianfni"/><path class="in2__ug-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:face" /></template>
