<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx-x6g2ze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx-x6g2ze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:door-open" /></template>
