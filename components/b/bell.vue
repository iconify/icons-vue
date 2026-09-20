<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-m9x5g6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l-m9x5g6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:bell" /></template>
