<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n10napp6q.css';
import '../../css/z/zi-9qcbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n10napp6q"/><path class="zi-9qcbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:block-storage" /></template>
