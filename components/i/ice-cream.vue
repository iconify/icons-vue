<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9ms98rdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b9ms98rdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:ice-cream" /></template>
