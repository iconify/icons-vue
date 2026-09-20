<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g18k1pb8p.css';
import '../../css/s/s4_j3-_9s.css';
import '../../css/i/i7sr6ubzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g18k1pb8p"/><path class="s4_j3-_9s"/><path class="i7sr6ubzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:image-solid" /></template>
