<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em_bebfok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em_bebfok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-horizontal" /></template>
