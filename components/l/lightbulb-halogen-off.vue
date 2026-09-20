<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec4rpzbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec4rpzbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-halogen-off" /></template>
