<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqc054xmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqc054xmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:chromecast" /></template>
