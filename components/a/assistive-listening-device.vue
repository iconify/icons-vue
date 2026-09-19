<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg575skup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg575skup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:assistive-listening-device" /></template>
