<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0_e6cbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a0_e6cbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-circle-fill-20" /></template>
