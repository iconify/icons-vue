<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2k6cl0mo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2k6cl0mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-minus" /></template>
