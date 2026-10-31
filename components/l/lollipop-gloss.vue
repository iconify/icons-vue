<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wasdvd6ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wasdvd6ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lollipop-gloss" /></template>
