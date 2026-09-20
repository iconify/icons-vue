<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt7khlbia.css';
import '../../css/i/ib0lxob6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt7khlbia"/><path class="ib0lxob6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ar" /></template>
