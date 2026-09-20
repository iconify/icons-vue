<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7iv0c6ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7iv0c6ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:corner-up-left-fill" /></template>
