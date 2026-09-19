<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsg-6dv6p.css';
import '../../css/q/quljz8buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsg-6dv6p"/><path class="quljz8buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-user-account" /></template>
