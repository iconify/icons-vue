<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3_weibsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3_weibsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:france2" /></template>
