<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6v13pvko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h6v13pvko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:feather-pen-remix" /></template>
