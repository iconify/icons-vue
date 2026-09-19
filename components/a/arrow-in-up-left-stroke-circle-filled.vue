<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxbgy5bzx.css';
import '../../css/l/l_-go266m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxbgy5bzx"/><path class="l_-go266m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-up-left-stroke-circle-filled" /></template>
