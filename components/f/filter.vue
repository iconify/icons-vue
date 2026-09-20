<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph9nw1sum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ph9nw1sum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:filter" /></template>
