<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-ipzbw6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-ipzbw6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:excalidraw" /></template>
