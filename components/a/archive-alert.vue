<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cse2x4o0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cse2x4o0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:archive-alert" /></template>
