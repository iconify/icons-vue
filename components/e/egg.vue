<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgg3rfb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mgg3rfb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:egg" /></template>
