<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itd-o_bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itd-o_bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:binge" /></template>
