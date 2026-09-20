<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-eqzibed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-eqzibed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:clapperboard-ai-line" /></template>
