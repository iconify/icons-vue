<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b93j9cbjr.css';
import '../../css/r/r389qlbwq.css';
import '../../css/i/iirdoip_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b93j9cbjr"/><path class="r389qlbwq"/><circle class="iirdoip_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:compass" /></template>
