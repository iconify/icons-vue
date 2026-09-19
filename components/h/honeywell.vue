<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju1k4hbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju1k4hbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:honeywell" /></template>
