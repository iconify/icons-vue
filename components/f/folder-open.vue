<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvixafbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="bvixafbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:folder-open" /></template>
