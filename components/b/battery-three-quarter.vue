<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbb0sudeg.css';
import '../../css/k/k743-oxfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wbb0sudeg"/><path clip-rule="evenodd" class="k743-oxfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:battery-three-quarter" /></template>
