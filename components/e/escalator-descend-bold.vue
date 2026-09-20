<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iabj60bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iabj60bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:escalator-descend-bold" /></template>
