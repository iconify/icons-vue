<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqfo8ifwt.css';
import '../../css/k/kc03hjs4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqfo8ifwt"/><path class="kc03hjs4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:chart-bar" /></template>
