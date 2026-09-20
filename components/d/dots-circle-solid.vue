<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4ge6fb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4ge6fb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dots-circle-solid" /></template>
