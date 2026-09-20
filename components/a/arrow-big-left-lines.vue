<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz8fjpbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz8fjpbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-big-left-lines" /></template>
