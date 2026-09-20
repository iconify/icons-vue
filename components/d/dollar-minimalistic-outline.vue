<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh2o2ku1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nh2o2ku1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dollar-minimalistic-outline" /></template>
