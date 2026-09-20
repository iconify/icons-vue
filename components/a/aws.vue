<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpj9x5mgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpj9x5mgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:aws" /></template>
