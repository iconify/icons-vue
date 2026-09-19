<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkfjl_8-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="rkfjl_8-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:football-ball" /></template>
