<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd6x0abcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd6x0abcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:cloud-disable" /></template>
