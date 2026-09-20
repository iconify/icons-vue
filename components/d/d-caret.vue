<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm78aw60m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sm78aw60m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:d-caret" /></template>
