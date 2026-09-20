<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik9np1c8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik9np1c8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:circle-multiple-outline" /></template>
