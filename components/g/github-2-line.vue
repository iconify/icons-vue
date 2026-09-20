<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz7d6xiyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz7d6xiyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:github-2-line" /></template>
