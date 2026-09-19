<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu122ac1g.css';
import '../../css/s/s0ax18b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu122ac1g"/><path class="s0ax18b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:arrowhead-right-fill" /></template>
