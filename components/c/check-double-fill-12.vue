<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of6vnd3yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="of6vnd3yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-double-fill-12" /></template>
