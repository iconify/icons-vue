<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_mk0nbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_mk0nbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cast-solid" /></template>
