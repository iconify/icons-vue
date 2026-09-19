<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th28v3ozw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th28v3ozw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-sultan-group-v2" /></template>
