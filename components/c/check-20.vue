<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdxrnm0ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mdxrnm0ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-20" /></template>
