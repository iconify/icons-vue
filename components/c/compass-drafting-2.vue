<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx1b5gb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx1b5gb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:compass-drafting-2" /></template>
