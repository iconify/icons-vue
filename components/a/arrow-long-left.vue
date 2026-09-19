<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp9qvac5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="pp9qvac5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-long-left" /></template>
