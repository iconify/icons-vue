<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1kwab81w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":512};
const content = `<path class="c1kwab81w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:lightning" /></template>
