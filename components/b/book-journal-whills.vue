<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajnikkn8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ajnikkn8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:book-journal-whills" /></template>
