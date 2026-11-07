<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgns90b-d.css';
import '../../css/e/ekudvch8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgns90b-d"/><path class="ekudvch8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:exclamation-mark-bold" /></template>
