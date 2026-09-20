<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw6cgiv-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw6cgiv-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:ai-model-24" /></template>
