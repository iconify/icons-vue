<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixo8itb4g.css';
import '../../css/k/k0mq39bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixo8itb4g"/><path class="k0mq39bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:location-alt-2-filled" /></template>
