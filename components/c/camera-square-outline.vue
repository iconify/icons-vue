<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezx0-pv8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ezx0-pv8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:camera-square-outline" /></template>
