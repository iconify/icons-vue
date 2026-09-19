<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyf6e2qlo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lyf6e2qlo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-warning" /></template>
