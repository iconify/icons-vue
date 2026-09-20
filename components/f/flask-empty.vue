<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0ygaxjmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="n0ygaxjmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:flask-empty" /></template>
