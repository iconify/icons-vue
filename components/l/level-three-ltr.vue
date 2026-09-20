<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_4aq0bli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x_4aq0bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:level-three-ltr" /></template>
