<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4_1llqee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="s4_1llqee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-narrow-right" /></template>
