<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkac35u9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jkac35u9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:imdb" /></template>
