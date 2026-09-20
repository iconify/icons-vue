<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7wes6u6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7wes6u6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:clapperboard-line" /></template>
