<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4tm_e4lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4tm_e4lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:brand-codepen-solid" /></template>
