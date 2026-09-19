<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw7dfbv7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jw7dfbv7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:glove" /></template>
