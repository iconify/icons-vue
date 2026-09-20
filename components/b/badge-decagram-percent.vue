<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg6hbfl5t.css';
import '../../css/o/o7-xjtbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg6hbfl5t"/><path clip-rule="evenodd" class="o7-xjtbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:badge-decagram-percent" /></template>
