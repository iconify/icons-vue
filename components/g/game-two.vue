<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_d9w8b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a_d9w8b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:game-two" /></template>
