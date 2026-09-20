<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b19yjd4da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b19yjd4da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:frame-outline" /></template>
