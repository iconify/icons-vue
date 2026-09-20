<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl2jszi2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl2jszi2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-network-sharp" /></template>
