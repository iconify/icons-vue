<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw9ue2s1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw9ue2s1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-card" /></template>
