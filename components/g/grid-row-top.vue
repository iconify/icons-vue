<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g32dqhbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g32dqhbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:grid-row-top" /></template>
