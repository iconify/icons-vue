<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn1vqfd2n.css';
import '../../css/r/r4tc83xlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yn1vqfd2n"/><path class="r4tc83xlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-epdf" /></template>
