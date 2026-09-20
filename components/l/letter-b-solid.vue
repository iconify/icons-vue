<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_isx3wzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_isx3wzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-b-solid" /></template>
