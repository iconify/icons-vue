<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkbu6xuoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkbu6xuoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bluetooth-off-line" /></template>
