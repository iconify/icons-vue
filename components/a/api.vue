<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuuoc0zvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuuoc0zvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:api" /></template>
