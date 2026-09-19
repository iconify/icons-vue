<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cantnxqek.css';
import '../../css/a/aodxntc9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cantnxqek"/><path class="aodxntc9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-import" /></template>
