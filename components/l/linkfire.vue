<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytrzksqzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytrzksqzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:linkfire" /></template>
