<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2-hc7e0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2-hc7e0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:fritz-repeater" /></template>
