<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzas9hb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gzas9hb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:corner" /></template>
