<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcf7zrb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rcf7zrb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cake2" /></template>
