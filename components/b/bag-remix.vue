<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcb66cb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jcb66cb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:bag-remix" /></template>
