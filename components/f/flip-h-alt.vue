<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8-ajz3mr.css';
import '../../css/c/cw9ts4b7s.css';
import '../../css/l/lv8kz-w7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8-ajz3mr"/><path class="cw9ts4b7s"/><path class="lv8kz-w7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:flip-h-alt" /></template>
