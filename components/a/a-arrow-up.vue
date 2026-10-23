<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv1watb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv1watb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:a-arrow-up" /></template>
