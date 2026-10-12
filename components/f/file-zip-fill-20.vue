<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rji5-yomq.css';
import '../../css/o/o1xu07rok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rji5-yomq"/><path class="o1xu07rok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-zip-fill-20" /></template>
