<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn65x6g0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn65x6g0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:github-fill-round" /></template>
