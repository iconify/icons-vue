<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emiwmpdsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emiwmpdsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-time-twelve-outline" /></template>
