<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sookxta7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sookxta7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:dongchedi" /></template>
