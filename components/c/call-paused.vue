<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb9xl5bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb9xl5bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call-paused" /></template>
