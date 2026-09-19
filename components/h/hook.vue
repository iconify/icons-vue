<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnq77hb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nnq77hb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:hook" /></template>
