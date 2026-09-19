<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttd3jyrng.css';
import '../../css/v/v7rhl_77b.css';
import '../../css/b/burecob8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ttd3jyrng"/><path class="v7rhl_77b"/><path class="burecob8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:certificate-check" /></template>
