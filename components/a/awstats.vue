<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br8161bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="br8161bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:awstats" /></template>
