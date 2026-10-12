<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acea_pbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="acea_pbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:hashtag-20" /></template>
