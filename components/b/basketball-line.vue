<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr3roy_bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr3roy_bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:basketball-line" /></template>
