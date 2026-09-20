<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbd42eb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbd42eb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-big-up-line-filled" /></template>
