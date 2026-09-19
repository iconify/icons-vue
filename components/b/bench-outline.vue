<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqhngwt5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="cqhngwt5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bench-outline" /></template>
