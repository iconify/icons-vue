<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqoho4b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqoho4b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:email-check-outline" /></template>
