<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6gjfe24p.css';
import '../../css/r/r4tc83xlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r6gjfe24p"/><path class="r4tc83xlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-word-processor" /></template>
