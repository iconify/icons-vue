<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5gf3tbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u5gf3tbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:arrow-up-bold" /></template>
