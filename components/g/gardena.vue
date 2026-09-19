<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqd774bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqd774bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:gardena" /></template>
