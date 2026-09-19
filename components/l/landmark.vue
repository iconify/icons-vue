<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di7kuibib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di7kuibib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:landmark" /></template>
