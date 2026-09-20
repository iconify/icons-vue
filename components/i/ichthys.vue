<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwqjbqb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iwqjbqb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ichthys" /></template>
