<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijhq98bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijhq98bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:charging-bolt" /></template>
