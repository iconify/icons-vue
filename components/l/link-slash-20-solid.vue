<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8nu7c66p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="x8nu7c66p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:link-slash-20-solid" /></template>
