<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmsj9h2cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmsj9h2cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dead" /></template>
