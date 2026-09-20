<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alf0tiuoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="alf0tiuoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:border-bottom" /></template>
