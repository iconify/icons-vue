<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trs6t6_2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trs6t6_2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:doube-window-closed" /></template>
