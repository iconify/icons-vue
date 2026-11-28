<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljw_bfb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljw_bfb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-check-solid" /></template>
