<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em43jyu1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em43jyu1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:help-filled" /></template>
