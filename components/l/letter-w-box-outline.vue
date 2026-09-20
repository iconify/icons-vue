<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nks7owb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nks7owb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-w-box-outline" /></template>
