<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5f070bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="j5f070bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:circumflex" /></template>
