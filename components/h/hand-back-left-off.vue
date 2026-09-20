<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhct0z40r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhct0z40r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hand-back-left-off" /></template>
