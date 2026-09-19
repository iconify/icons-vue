<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot-y1i3we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot-y1i3we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-circle-up-filled" /></template>
