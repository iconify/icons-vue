<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jutc71b_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jutc71b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-narrow-left" /></template>
