<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wutb45b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wutb45b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:globe-x-fill" /></template>
