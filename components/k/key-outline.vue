<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brn89rbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="brn89rbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:key-outline" /></template>
