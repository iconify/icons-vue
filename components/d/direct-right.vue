<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whrvgkbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whrvgkbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:direct-right" /></template>
