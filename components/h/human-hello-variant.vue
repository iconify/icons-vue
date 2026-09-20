<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5u8ltlqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5u8ltlqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-hello-variant" /></template>
