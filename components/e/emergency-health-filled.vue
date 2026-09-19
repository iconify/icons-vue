<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udd-1hb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udd-1hb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:emergency-health-filled" /></template>
