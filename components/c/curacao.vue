<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7jllbb4j.css';
import '../../css/b/bx4_vlbad.css';
import '../../css/n/n3enlbj8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="l7jllbb4j"/><path class="bx4_vlbad"/><path class="n3enlbj8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:curacao" /></template>
