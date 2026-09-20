<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm_my446l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm_my446l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bulb-off" /></template>
