<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4spd6uww.css';
import '../../css/a/ag-fl02wi.css';
import '../../css/d/d7aps8ede.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m4spd6uww"/><path class="ag-fl02wi"/><path class="d7aps8ede"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:content-files-open-book-bookmark" /></template>
