<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxjtsz59o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxjtsz59o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:christmas-ball-line" /></template>
