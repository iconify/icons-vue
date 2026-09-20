<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st4u3kabo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="st4u3kabo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:add-layer-2-remix" /></template>
