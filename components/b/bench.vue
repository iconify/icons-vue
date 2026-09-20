<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0eluub0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c0eluub0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:bench" /></template>
