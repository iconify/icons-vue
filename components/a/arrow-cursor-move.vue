<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh08u7trk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kh08u7trk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:arrow-cursor-move" /></template>
