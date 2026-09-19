<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp2abxbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="sp2abxbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-trending-fill-12" /></template>
