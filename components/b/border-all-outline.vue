<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hui9kbcjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hui9kbcjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:border-all-outline" /></template>
