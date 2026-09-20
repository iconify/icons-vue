<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygyfef5pg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ygyfef5pg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:camera-record-filled" /></template>
