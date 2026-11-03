<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e71i78b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="e71i78b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:leaf-20-solid" /></template>
