<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6v1cwyio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n6v1cwyio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ethereum-circle-remix" /></template>
