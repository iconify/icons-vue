<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4fzszs3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v4fzszs3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kometa-light" /></template>
