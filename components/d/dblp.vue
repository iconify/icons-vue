<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kylvxgb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="kylvxgb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:dblp" /></template>
