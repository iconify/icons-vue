<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twgt3wb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="twgt3wb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:document-arrow-up" /></template>
