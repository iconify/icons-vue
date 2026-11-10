<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0-3g3rak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="g0-3g3rak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:folder-arrow-path-20-solid" /></template>
