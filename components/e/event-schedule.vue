<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-kkh0h8n.css';
import '../../css/k/kj5p4ecrw.css';
import '../../css/n/n_757dk6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s-kkh0h8n"/><path class="kj5p4ecrw"/><path class="n_757dk6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:event-schedule" /></template>
