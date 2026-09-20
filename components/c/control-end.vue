<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqc0zky1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kqc0zky1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:control-end" /></template>
