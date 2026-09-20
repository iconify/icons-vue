<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgkky5bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pgkky5bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:facebook-1-solid" /></template>
