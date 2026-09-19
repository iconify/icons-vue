<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3tor9bcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3tor9bcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dreamcast" /></template>
