<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qog4gacfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qog4gacfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:gallery-fill" /></template>
