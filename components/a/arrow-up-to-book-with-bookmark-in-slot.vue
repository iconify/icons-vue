<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9_iqvdnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p9_iqvdnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-up-to-book-with-bookmark-in-slot" /></template>
