<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o21yy6bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="o21yy6bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:bandcamp" /></template>
