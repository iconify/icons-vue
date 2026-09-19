<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7l2_07fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7l2_07fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:book-open" /></template>
