<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp7wb5b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fp7wb5b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:dots-x" /></template>
