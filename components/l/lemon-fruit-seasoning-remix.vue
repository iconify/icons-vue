<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o15dx7bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o15dx7bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:lemon-fruit-seasoning-remix" /></template>
