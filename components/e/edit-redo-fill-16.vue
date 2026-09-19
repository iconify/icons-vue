<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9ym0t80c.css';
import '../../css/a/ae-rsdbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v9ym0t80c"/><path class="ae-rsdbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:edit-redo-fill-16" /></template>
