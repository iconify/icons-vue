<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k49s1-b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="k49s1-b9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:checkboxalt" /></template>
