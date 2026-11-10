<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4vdj2bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j4vdj2bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-arrow-path-20-solid" /></template>
