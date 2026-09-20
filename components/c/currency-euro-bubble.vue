<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imklbhx5a.css';
import '../../css/g/g2u40lrig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imklbhx5a"/><path class="g2u40lrig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:currency-euro-bubble" /></template>
