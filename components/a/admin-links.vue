<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei08f3b-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ei08f3b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:admin-links" /></template>
