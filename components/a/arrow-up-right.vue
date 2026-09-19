<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuody5sya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="iuody5sya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-up-right" /></template>
