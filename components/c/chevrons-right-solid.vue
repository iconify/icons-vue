<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibhx10bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibhx10bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevrons-right-solid" /></template>
