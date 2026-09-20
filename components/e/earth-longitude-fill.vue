<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2e7ncbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2e7ncbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:earth-longitude-fill" /></template>
