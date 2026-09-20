<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s568gputr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s568gputr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ergo-light" /></template>
