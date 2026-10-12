<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a24-d1bxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a24-d1bxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:emoji-grin-fill-20" /></template>
