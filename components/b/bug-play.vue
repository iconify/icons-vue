<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umax9m-3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umax9m-3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bug-play" /></template>
