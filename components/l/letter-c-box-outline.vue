<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqr00dbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqr00dbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-c-box-outline" /></template>
