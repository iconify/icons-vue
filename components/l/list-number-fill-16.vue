<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg3fqv7jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fg3fqv7jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:list-number-fill-16" /></template>
