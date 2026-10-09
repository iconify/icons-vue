<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fec4cjbkq.css';
import '../../css/x/xu4qvpb9q.css';
import '../../css/k/kzkcy1d2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fec4cjbkq"/><path class="xu4qvpb9q"/><path class="kzkcy1d2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-up-square-20-bold" /></template>
