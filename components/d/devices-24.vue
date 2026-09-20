<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry2iipgfe.css';
import '../../css/p/p1xj-fcxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry2iipgfe"/><path class="p1xj-fcxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:devices-24" /></template>
