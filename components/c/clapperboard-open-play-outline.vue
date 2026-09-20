<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl-vh0b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gl-vh0b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clapperboard-open-play-outline" /></template>
