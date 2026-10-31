<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csk8wdbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csk8wdbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-right-large-duocolor-round" /></template>
