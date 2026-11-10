<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kajv0hbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kajv0hbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:folder-exclamation-16-solid" /></template>
