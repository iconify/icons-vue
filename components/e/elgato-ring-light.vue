<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsp71pmgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsp71pmgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:elgato-ring-light" /></template>
