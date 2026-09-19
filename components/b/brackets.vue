<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysfr6k0aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysfr6k0aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:brackets" /></template>
