<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvbpqrsoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mvbpqrsoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:islam-remix" /></template>
