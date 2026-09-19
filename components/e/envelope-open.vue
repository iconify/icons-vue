<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpmku4bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="tpmku4bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:envelope-open" /></template>
