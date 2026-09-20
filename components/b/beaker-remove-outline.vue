<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sckf1ebqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sckf1ebqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:beaker-remove-outline" /></template>
