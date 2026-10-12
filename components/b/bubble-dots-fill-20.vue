<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcaj3m83n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rcaj3m83n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bubble-dots-fill-20" /></template>
