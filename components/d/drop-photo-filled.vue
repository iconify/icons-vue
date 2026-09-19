<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqj6aujyf.css';
import '../../css/n/n0guy7nbp.css';
import '../../css/b/b-7bc9b_n.css';
import '../../css/l/l1xsbgjra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="sqj6aujyf"/><path class="n0guy7nbp"/><path class="b-7bc9b_n"/><path class="l1xsbgjra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:drop-photo-filled" /></template>
