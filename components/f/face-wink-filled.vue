<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u393f9bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u393f9bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:face-wink-filled" /></template>
