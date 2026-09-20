<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adw19fflm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adw19fflm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:incoming-call" /></template>
