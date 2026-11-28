<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igjbv8bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igjbv8bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:chevron-circle-right" /></template>
