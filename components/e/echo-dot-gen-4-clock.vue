<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm7s0jbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm7s0jbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:echo-dot-gen-4-clock" /></template>
