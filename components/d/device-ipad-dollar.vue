<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku0n0gbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku0n0gbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-dollar" /></template>
