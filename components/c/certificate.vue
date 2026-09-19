<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0y0atbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="h0y0atbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:certificate" /></template>
