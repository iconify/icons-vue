<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nor8u-b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nor8u-b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:framer-outline" /></template>
