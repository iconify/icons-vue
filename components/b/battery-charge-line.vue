<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeyxizf-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qeyxizf-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:battery-charge-line" /></template>
