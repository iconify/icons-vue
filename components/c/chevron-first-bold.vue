<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyc9-xbym.css';
import '../../css/u/uou3acccj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyc9-xbym"/><path class="uou3acccj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevron-first-bold" /></template>
