<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqwujhbmd.css';
import '../../css/t/t2-05fbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hqwujhbmd"/><path class="t2-05fbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:left-to-right-16" /></template>
