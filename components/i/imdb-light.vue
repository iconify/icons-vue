<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axc2gplka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="axc2gplka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:imdb-light" /></template>
