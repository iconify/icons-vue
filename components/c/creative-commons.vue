<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kalrokb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="kalrokb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:creative-commons" /></template>
