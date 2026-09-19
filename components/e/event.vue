<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_757dk6o.css';
import '../../css/t/the1faccv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n_757dk6o"/><path class="the1faccv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:event" /></template>
