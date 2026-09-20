<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xluqg_7ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xluqg_7ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:google-fill" /></template>
