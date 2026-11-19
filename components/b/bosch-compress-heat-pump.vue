<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbecrtbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbecrtbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bosch-compress-heat-pump" /></template>
