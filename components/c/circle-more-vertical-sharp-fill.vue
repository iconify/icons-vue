<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8f4ehb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8f4ehb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-more-vertical-sharp-fill" /></template>
