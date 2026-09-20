<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipimt7btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipimt7btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:egg-cup" /></template>
