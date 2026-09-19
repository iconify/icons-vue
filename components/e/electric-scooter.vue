<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am-5-p8-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am-5-p8-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:electric-scooter" /></template>
