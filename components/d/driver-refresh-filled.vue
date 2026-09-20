<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syr6mpbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syr6mpbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:driver-refresh-filled" /></template>
