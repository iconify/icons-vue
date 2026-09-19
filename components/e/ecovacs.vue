<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0aqn2g6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0aqn2g6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ecovacs" /></template>
