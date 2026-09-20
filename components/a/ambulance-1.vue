<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6l40s97s.css';
import '../../css/l/l08ti_b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6l40s97s"/><path clip-rule="evenodd" class="l08ti_b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ambulance-1" /></template>
