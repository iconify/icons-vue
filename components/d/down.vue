<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsuq8tbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wsuq8tbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:down" /></template>
