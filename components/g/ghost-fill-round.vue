<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s980kpblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s980kpblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ghost-fill-round" /></template>
