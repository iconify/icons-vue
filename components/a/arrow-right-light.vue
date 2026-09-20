<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1mst_bla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1mst_bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:arrow-right-light" /></template>
