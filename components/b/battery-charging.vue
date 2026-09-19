<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxaj23pjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxaj23pjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:battery-charging" /></template>
