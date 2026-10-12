<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2neunb3u.css';
import '../../css/a/a600ktbsl.css';
import '../../css/l/l1xb2ibbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n2neunb3u"/><path class="a600ktbsl"/><path class="l1xb2ibbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-circle-right-48-bold" /></template>
