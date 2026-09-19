<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5ygdbczq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p5ygdbczq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:fast-arrow-up-square-solid" /></template>
