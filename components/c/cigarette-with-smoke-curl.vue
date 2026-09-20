<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au_v0wb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="au_v0wb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cigarette-with-smoke-curl" /></template>
