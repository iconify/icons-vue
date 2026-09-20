<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bisslo7yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bisslo7yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:idia" /></template>
