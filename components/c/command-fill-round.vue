<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q48-8fbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q48-8fbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:command-fill-round" /></template>
