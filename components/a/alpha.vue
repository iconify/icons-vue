<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrdrucbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrdrucbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:alpha" /></template>
