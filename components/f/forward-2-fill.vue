<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5yd7u01h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5yd7u01h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:forward-2-fill" /></template>
