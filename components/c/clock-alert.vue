<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-rh7-bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-rh7-bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clock-alert" /></template>
