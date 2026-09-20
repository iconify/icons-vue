<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axwlv8_bk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axwlv8_bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chart5-filled" /></template>
