<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7betk-dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="b7betk-dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-path-clock-20-solid" /></template>
