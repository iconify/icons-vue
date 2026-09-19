<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvsxk8p_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvsxk8p_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-classic-hung-4" /></template>
