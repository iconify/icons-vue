<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqu3fyexs.css';
import '../../css/b/b4mh51b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqu3fyexs"/><path clip-rule="evenodd" class="b4mh51b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:fortune-telling-sphere-solid" /></template>
