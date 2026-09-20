<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smod414ny.css';
import '../../css/o/ol4ckq3wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smod414ny"/><path class="ol4ckq3wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:log-24" /></template>
