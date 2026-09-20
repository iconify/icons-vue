<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq3qa1d7q.css';
import '../../css/i/itgv6gmfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq3qa1d7q"/><path class="itgv6gmfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:chart" /></template>
