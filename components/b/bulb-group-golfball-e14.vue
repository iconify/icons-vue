<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it67cvzui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it67cvzui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-golfball-e14" /></template>
