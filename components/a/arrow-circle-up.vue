<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilj-16bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilj-16bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:arrow-circle-up" /></template>
