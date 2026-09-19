<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx131-biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx131-biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-alarm-off" /></template>
