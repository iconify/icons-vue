<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjqtc9kwq.css';
import '../../css/n/nod8k7bwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="sjqtc9kwq"/><circle class="nod8k7bwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-flickr" /></template>
