<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuc_41kpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fuc_41kpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-narrow-up" /></template>
