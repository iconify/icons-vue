<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lai_9vqlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lai_9vqlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:battery-empty" /></template>
