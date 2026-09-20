<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9wan6knc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m9wan6knc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:cloud" /></template>
