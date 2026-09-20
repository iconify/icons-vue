<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk0n2ybxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk0n2ybxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-cog" /></template>
