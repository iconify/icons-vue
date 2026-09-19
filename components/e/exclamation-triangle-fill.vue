<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jevk7xbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jevk7xbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:exclamation-triangle-fill" /></template>
