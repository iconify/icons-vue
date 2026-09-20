<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-g4q9p2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-g4q9p2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-heading-equal" /></template>
