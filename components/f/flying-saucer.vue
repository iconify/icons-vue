<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-iyp4zor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h-iyp4zor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:flying-saucer" /></template>
