<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwwck0bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cwwck0bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:headphones-slash-thin" /></template>
