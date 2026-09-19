<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp3yqspdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":1280};
const content = `<path class="fp3yqspdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:caret-left" /></template>
