<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s33ltlbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s33ltlbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:clapperboard-play-solid" /></template>
