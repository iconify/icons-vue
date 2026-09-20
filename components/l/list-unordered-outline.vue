<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hom7et23z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hom7et23z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:list-unordered-outline" /></template>
