<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awxbmobeb.css';
import '../../css/u/utdolccoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awxbmobeb"/><path class="utdolccoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:copi" /></template>
