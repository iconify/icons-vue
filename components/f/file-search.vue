<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tipmx-bid.css';
import '../../css/g/gnxrllo6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tipmx-bid"/><path class="gnxrllo6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:file-search" /></template>
