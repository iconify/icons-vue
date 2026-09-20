<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkooupbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkooupbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:done2-filled" /></template>
