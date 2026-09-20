<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-wk0oblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f-wk0oblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:detergent-bottle" /></template>
