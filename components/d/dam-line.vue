<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weg5p8w9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="weg5p8w9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dam-line" /></template>
