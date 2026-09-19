<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu1f9cb1q.css';
import '../../css/e/ebmyan6qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mu1f9cb1q"/><path class="ebmyan6qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:bottom-right" /></template>
