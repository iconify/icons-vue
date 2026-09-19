<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioc0cybks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ioc0cybks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:battery-medium-01" /></template>
