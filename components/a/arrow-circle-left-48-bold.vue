<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2neunb3u.css';
import '../../css/o/oyr60yb7q.css';
import '../../css/t/tkn0jlbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n2neunb3u"/><path class="oyr60yb7q"/><path class="tkn0jlbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-circle-left-48-bold" /></template>
