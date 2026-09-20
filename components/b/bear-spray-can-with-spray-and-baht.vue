<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7l6k569g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u7l6k569g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bear-spray-can-with-spray-and-baht" /></template>
