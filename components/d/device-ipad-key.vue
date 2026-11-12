<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i94675ujg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i94675ujg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-key" /></template>
