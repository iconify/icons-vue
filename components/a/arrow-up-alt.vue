<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9_h9ldng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s9_h9ldng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:arrow-up-alt" /></template>
