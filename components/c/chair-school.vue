<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn1t_absc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn1t_absc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chair-school" /></template>
