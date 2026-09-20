<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s92f2jh7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s92f2jh7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cannabis-solid" /></template>
