<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbm5cab-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbm5cab-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:keyboard-shift" /></template>
