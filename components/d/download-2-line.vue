<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf0rr5b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf0rr5b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:download-2-line" /></template>
