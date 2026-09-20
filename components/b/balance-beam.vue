<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb0dbsb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pb0dbsb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:balance-beam" /></template>
