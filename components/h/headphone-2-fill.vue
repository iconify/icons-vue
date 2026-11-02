<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-xp3dbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-xp3dbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:headphone-2-fill" /></template>
