<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r209j7-tl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r209j7-tl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:abc-iview" /></template>
