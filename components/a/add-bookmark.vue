<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czij1r9ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="czij1r9ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:add-bookmark" /></template>
