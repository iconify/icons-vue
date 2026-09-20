<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijw6f5b1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijw6f5b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fluxus" /></template>
