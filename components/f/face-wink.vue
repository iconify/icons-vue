<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cymb9cbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cymb9cbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:face-wink" /></template>
