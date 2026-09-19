<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g81rw9b8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="g81rw9b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:id-badge" /></template>
