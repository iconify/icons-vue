<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfe1kszww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfe1kszww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:forward" /></template>
