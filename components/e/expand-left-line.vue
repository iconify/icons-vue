<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijow_obmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijow_obmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-left-line" /></template>
