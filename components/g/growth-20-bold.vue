<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjtcl1bev.css';
import '../../css/a/a7u6cyhmr.css';
import '../../css/b/b5w0wtb3k.css';
import '../../css/s/s-x7mwb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kjtcl1bev"/><path class="a7u6cyhmr"/><path class="b5w0wtb3k"/><path class="s-x7mwb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:growth-20-bold" /></template>
