<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juufe7eyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juufe7eyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-turn-right-up-duotone-round" /></template>
