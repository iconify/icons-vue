<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tagpg-bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tagpg-bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:d-arrow-right" /></template>
