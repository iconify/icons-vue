<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3f2ys1ud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d3f2ys1ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:logo-yandex-ai-studio" /></template>
