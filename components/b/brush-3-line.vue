<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3yq0qbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3yq0qbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:brush-3-line" /></template>
