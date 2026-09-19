<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iza0mcbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iza0mcbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:appletv-sim" /></template>
