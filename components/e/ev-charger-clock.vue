<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvynwcrpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvynwcrpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:ev-charger-clock" /></template>
