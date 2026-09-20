<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az_f5k7uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az_f5k7uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-i-solid" /></template>
