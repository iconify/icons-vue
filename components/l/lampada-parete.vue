<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swz0mqbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swz0mqbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lampada-parete" /></template>
