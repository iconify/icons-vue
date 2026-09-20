<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swsrnjb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swsrnjb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brush-line" /></template>
