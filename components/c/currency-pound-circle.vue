<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg61hig3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg61hig3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:currency-pound-circle" /></template>
