<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpv5ewbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bpv5ewbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alarm-turn-off-outline" /></template>
