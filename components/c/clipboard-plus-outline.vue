<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b40zu7uku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b40zu7uku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:clipboard-plus-outline" /></template>
