<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bneixbc6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bneixbc6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gather-16" /></template>
