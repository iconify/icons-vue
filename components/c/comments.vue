<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2zvx5bln.css';
import '../../css/b/b3h4d4bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h2zvx5bln"/><path class="b3h4d4bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:comments" /></template>
