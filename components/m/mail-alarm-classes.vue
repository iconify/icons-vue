<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwbusqb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wwbusqb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:mail-alarm-classes" /></template>
