<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj10aeb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj10aeb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:grill-gas" /></template>
