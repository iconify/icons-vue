<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbs3iqbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbs3iqbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bluetooth-off" /></template>
