<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcpc46bqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcpc46bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:archive" /></template>
