<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjkuf-brx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bjkuf-brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:fahrenheit-remix" /></template>
