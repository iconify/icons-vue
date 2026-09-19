<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvs7ceb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bvs7ceb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:livestream" /></template>
