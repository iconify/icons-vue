<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owm-0ybmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owm-0ybmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:emergency-flashers-line" /></template>
