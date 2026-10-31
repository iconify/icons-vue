<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g46ojlx0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g46ojlx0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-turn-up-right-duotone-round" /></template>
