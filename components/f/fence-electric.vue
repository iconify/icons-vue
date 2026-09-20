<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to364ober.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to364ober"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fence-electric" /></template>
