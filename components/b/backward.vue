<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrradhcvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1568,"height":1536};
const content = `<path class="qrradhcvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:backward" /></template>
