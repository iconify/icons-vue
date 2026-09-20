<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2sjr9b1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p2sjr9b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:gramophone-solid" /></template>
