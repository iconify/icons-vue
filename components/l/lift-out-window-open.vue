<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy6m6hb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy6m6hb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lift-out-window-open" /></template>
