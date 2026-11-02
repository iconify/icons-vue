<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw5xzmb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw5xzmb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrows-right-fill" /></template>
