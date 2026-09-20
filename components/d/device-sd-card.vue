<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-_qc3pzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-_qc3pzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-sd-card" /></template>
