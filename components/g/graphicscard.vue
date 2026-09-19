<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb4cbr40k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lb4cbr40k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:graphicscard" /></template>
