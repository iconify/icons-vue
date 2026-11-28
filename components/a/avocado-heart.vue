<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl_qniicf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl_qniicf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:avocado-heart" /></template>
