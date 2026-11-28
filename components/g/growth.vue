<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvq-8lb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvq-8lb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:growth" /></template>
