<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9io2_wvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9io2_wvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:gallery-vertical" /></template>
