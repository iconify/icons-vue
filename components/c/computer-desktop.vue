<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kandx6b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="kandx6b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:computer-desktop" /></template>
