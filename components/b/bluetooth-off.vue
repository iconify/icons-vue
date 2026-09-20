<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi323x62o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi323x62o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bluetooth-off" /></template>
