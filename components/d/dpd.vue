<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmy18lb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmy18lb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dpd" /></template>
