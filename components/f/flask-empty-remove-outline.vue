<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt1668jtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt1668jtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flask-empty-remove-outline" /></template>
