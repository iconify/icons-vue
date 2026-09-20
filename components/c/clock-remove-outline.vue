<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cexc4bw2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cexc4bw2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-remove-outline" /></template>
