<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2dnkwqwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n2dnkwqwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:dice-3-remix" /></template>
