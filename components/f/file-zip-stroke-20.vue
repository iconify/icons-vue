<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l46lvfrxi.css';
import '../../css/g/g07kyqb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l46lvfrxi"/><path class="g07kyqb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-zip-stroke-20" /></template>
