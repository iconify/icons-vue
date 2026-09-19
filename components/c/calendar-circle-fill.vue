<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrn8-zb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qrn8-zb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:calendar-circle-fill" /></template>
