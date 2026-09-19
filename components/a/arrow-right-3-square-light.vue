<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocy1dtl3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocy1dtl3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-right-3-square-light" /></template>
