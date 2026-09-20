<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx3n_tb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gx3n_tb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-k-diamond-solid" /></template>
