<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcpry4u-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tcpry4u-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clock-circle-bold" /></template>
